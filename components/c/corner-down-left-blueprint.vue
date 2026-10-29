<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/c/c6e--ab3b.css';
import '../../css/e/e49usltee.css';
import '../../css/d/d8jrfxbex.css';
import '../../css/g/g37caurxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="c6e--ab3b wm-k"/><path class="e49usltee wm-a"/><path class="d8jrfxbex wm-k"/><path class="g37caurxe wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:corner-down-left-blueprint" /></template>
