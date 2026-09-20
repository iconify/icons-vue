<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o39tw9d9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o39tw9d9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:lamp" /></template>
