<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zg_0asz9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zg_0asz9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:arrow-right" /></template>
