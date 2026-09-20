<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/n9vomcc2d.css';
import '../../css/n/n5fjpab4o.css';
import '../../css/q/q90e-8amo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="n9vomcc2d"/><path class="n5fjpab4o"/><path class="q90e-8amo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:inbox-unread-bold-duotone" /></template>
