<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_yxm_tx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gp_yxm_tx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:grid-2x2-plus-fill" /></template>
