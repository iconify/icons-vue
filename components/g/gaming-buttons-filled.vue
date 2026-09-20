<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/np_3uwb3h.css';
import '../../css/y/y7wm307so.css';
import '../../css/p/pwa13k8ww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><rect class="np_3uwb3h"/><circle class="y7wm307so"/><path class="pwa13k8ww"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:gaming-buttons-filled" /></template>
