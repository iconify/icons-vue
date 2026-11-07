<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/x/xvjk-cbox.css';
import '../../css/s/s5dde6qgk.css';
import '../../css/i/ix8cskbcl.css';
import '../../css/z/z4e6-1p3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xvjk-cbox"/><path class="s5dde6qgk"/><path class="ix8cskbcl"/><path class="z4e6-1p3b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:clapperboard-text-line-duotone" /></template>
