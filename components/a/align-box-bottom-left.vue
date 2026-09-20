<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/etg_j4bre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="etg_j4bre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:align-box-bottom-left" /></template>
