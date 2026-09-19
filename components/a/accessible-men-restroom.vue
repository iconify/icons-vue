<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwv5vgb1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bwv5vgb1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:accessible-men-restroom" /></template>
