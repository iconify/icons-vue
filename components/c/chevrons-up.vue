<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/s/s3jlzcczn.css';
import '../../css/f/fuoff3b8g.css';
import '../../css/j/jm92ox9fv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="s3jlzcczn wm-shadow"/><path class="fuoff3b8g wm-shadow"/><path class="jm92ox9fv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:chevrons-up" /></template>
