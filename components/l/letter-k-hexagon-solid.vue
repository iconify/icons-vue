<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzl802ntq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tzl802ntq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-k-hexagon-solid" /></template>
