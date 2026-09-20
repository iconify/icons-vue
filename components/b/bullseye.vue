<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8ecjla3i.css';
import '../../css/u/ucqje3dcn.css';
import '../../css/b/bl_qslbwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="s8ecjla3i"/><path class="ucqje3dcn"/><path class="bl_qslbwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:bullseye" /></template>
