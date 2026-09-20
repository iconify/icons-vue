<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/dee58dbgi.css';
import '../../css/o/o89k-3d4n.css';
import '../../css/c/c6069abgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="dee58dbgi"/><path class="o89k-3d4n"/><path class="c6069abgm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:file-edit" /></template>
