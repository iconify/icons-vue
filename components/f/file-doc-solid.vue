<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/fi_h3obyz.css';
import '../../css/i/ie7ewgb8j.css';
import '../../css/i/iupmgbczu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="fi_h3obyz"/><path clip-rule="evenodd" class="ie7ewgb8j"/><path class="iupmgbczu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:file-doc-solid" /></template>
