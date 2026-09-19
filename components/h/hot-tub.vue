<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6e-d3bum.css';
import '../../css/y/ykod1zf1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w6e-d3bum"/><path class="ykod1zf1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:hot-tub" /></template>
