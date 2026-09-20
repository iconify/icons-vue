<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5jbxh.css';
import '../../css/i/iw1iew.css';
import '../../css/e/eswpkb.css';
import '../../css/s/so-from-28.css';
import '../../css/f/fill-to-1.css';
import '../../css/f/fade-to-1.css';
import '../../css/d/d-z2xg2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c5jbxh iw1iew"/><path class="eswpkb iw1iew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:hazard-lights-filled" /></template>
