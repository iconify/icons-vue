<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ri2-alb5d.css';
import '../../css/c/cdcuj1bfy.css';
import '../../css/y/yeqb12bcq.css';
import '../../css/m/mi4ifbrrd.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 ri2-alb5d"/><path class="cdcuj1bfy clr-i-solid clr-i-solid-path-2"/><path class="clr-i-solid clr-i-solid-path-3 yeqb12bcq"/><path class="clr-i-solid clr-i-solid-path-4 mi4ifbrrd"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:archive-solid" /></template>
