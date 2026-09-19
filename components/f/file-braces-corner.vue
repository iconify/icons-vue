<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/z7nmpmbvj.css';
import '../../css/f/f05pcbspf.css';
import '../../css/i/i8nh24b2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="z7nmpmbvj"/><path class="f05pcbspf"/><path class="i8nh24b2r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:file-braces-corner" /></template>
