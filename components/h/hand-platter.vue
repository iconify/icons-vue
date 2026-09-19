<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/o/oh8kmobjf.css';
import '../../css/k/kxmnzabbx.css';
import '../../css/d/d-_z4m5uh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="oh8kmobjf"/><path class="kxmnzabbx"/><path class="d-_z4m5uh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:hand-platter" /></template>
