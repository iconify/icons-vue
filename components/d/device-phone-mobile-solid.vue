<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/y/ymxez2j2t.css';
import '../../css/y/y_cx2bazl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ymxez2j2t"/><path clip-rule="evenodd" class="y_cx2bazl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:device-phone-mobile-solid" /></template>
