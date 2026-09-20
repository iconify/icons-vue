<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/h/hj49fqb2n.css';
import '../../css/z/z2kaxubju.css';
import '../../css/f/f7a06bbbb.css';
import '../../css/t/tz2wjbb3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="hj49fqb2n"/><path class="z2kaxubju"/><path class="f7a06bbbb"/><path class="tz2wjbb3f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:email-logo" /></template>
