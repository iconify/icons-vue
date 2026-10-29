<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/k/k7e9fxb5e.css';
import '../../css/m/mvi8grbak.css';
import '../../css/b/bnjyj2b6y.css';
import '../../css/z/zhq9nbcqz.css';
import '../../css/l/lrg-fdc4r.css';
import '../../css/u/uqhmd6bht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="k7e9fxb5e wm-deco"/><path class="mvi8grbak wm-deco"/><path class="bnjyj2b6y wm-deco"/><path class="wm-k zhq9nbcqz"/><path class="lrg-fdc4r wm-a"/><path class="uqhmd6bht wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:chart-network-blueprint" /></template>
