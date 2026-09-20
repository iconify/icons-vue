<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tykev4j_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tykev4j_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:anaconda" /></template>
