<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nb5gi3b6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nb5gi3b6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:chevron-right" /></template>
