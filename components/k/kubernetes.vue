<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wt53_51gy.css';
import '../../css/j/jvxlq78ce.css';
import '../../css/j/j_vpq2bok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wt53_51gy"/><path class="jvxlq78ce"/><path class="j_vpq2bok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:kubernetes" /></template>
