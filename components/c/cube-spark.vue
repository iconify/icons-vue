<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dekd_hbaw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dekd_hbaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:cube-spark" /></template>
