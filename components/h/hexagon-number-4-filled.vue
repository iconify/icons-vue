<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5cgm049q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m5cgm049q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:hexagon-number-4-filled" /></template>
