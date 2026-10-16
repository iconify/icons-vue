<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6_s1zkbf.css';
import '../../css/g/gf-zaq-tp.css';
import '../../css/j/jfsyo7b1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="e6_s1zkbf"/><path class="gf-zaq-tp"/><path class="jfsyo7b1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hazard-toxic-20" /></template>
