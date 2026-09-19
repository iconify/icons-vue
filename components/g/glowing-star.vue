<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-4g368hm.css';
import '../../css/s/s11f4ob4t.css';
import '../../css/e/ew4v2q7dx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="y-4g368hm"><path class="s11f4ob4t"/><path class="ew4v2q7dx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:glowing-star" /></template>
