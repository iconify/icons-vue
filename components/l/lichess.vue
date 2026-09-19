<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/li9cd2o_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b li9cd2o_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:lichess" /></template>
