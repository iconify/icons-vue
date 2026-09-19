<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njswg3bpu.css';
import '../../css/v/v_g5t0bgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<ellipse class="njswg3bpu"/><path class="v_g5t0bgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:hole" /></template>
