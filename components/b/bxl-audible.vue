<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qo4xr7bel.css';
import '../../css/q/q4497hb1w.css';
import '../../css/s/s11q8obkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qo4xr7bel"/><path class="q4497hb1w"/><path class="s11q8obkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-audible" /></template>
