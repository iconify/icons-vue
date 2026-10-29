<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/b/b74rkzv8a.css';
import '../../css/m/mlr2voast.css';
import '../../css/s/shte9bcuj.css';
import '../../css/b/b83hx2bbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="b74rkzv8a wm-deco"/><path class="mlr2voast wm-k"/><path class="shte9bcuj wm-a"/><path class="b83hx2bbd wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:bell-off-blueprint" /></template>
