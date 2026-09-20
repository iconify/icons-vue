<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lnn81abvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="lnn81abvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:archive" /></template>
