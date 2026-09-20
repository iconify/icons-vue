<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vned2cgbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vned2cgbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:hexagon-number-8-filled" /></template>
