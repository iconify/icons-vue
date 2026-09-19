<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/se-clabae.css';
import '../../css/l/lq7wkubnx.css';
import '../../css/c/ch0i37b-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="se-clabae"/><path class="lq7wkubnx"/><path class="ch0i37b-m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:blossom" /></template>
