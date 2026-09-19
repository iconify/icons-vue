<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fyvy0x6vz.css';
import '../../css/n/nh4ls7l6o.css';
import '../../css/f/f_tbp8boy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<ellipse class="fyvy0x6vz"/><ellipse class="nh4ls7l6o"/><path class="f_tbp8boy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:bicep" /></template>
