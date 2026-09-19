<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qo4xr7bel.css';
import '../../css/h/h8zuyyb3g.css';
import '../../css/h/hv6ma6bat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qo4xr7bel"/><path class="h8zuyyb3g"/><path class="hv6ma6bat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:audible" /></template>
