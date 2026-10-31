<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ux3isacaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ux3isacaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:heart-gloss" /></template>
