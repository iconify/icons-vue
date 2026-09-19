<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ke3m0vsct.css';
import '../../css/j/jfaet3x_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ke3m0vsct"/><path class="jfaet3x_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:chevrons-left" /></template>
