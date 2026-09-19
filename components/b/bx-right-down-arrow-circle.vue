<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xaxv-gbpo.css';
import '../../css/x/xp00lybfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xaxv-gbpo"/><path class="xp00lybfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-right-down-arrow-circle" /></template>
