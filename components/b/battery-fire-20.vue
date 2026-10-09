<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9eubhbjc.css';
import '../../css/z/zp0_hubyv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="z9eubhbjc"/><path class="zp0_hubyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:battery-fire-20" /></template>
