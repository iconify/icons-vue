<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/b/brye_nbes.css';
import '../../css/c/cf3uzcrzx.css';
import '../../css/t/tm9-ayd9z.css';
import '../../css/c/c3wgojkty.css';
import '../../css/j/j6awffdnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="brye_nbes wm-deco"/><path class="cf3uzcrzx wm-deco"/><path class="tm9-ayd9z wm-k"/><path class="c3wgojkty wm-s"/><path class="j6awffdnl wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:list-plus-blueprint" /></template>
