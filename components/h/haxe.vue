<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qaiyq5bvp.css';
import '../../css/r/rdjuzybku.css';
import '../../css/z/zn1bxvb4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="qaiyq5bvp"><path class="rdjuzybku"/><path class="zn1bxvb4h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:haxe" /></template>
