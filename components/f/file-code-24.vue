<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iy6j6obsd.css';
import '../../css/e/e7yp3qfxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iy6j6obsd"/><path class="e7yp3qfxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:file-code-24" /></template>
