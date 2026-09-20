<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/phu1k1bve.css';
import '../../css/z/z5_p_eb1w.css';
import '../../css/y/y3qengbsr.css';
import '../../css/i/i25xlw0mu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="phu1k1bve"/><g class="z5_p_eb1w"><path class="y3qengbsr"/><path class="i25xlw0mu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-godot" /></template>
