<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bh-3wlb0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bh-3wlb0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:badge-info-gloss" /></template>
