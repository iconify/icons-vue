<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/k7fxwoh6a.css';
import '../../css/d/dh7dtzbik.css';
import '../../css/p/prwipib7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="k7fxwoh6a"/><path class="dh7dtzbik"/><path class="prwipib7r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:inbox-tray" /></template>
