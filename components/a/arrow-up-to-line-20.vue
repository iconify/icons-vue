<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c25jzkbsf.css';
import '../../css/w/wy4_yib2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c25jzkbsf"/><path class="wy4_yib2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrow-up-to-line-20" /></template>
