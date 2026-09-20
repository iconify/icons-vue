<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k07c9wb7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k07c9wb7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:loop" /></template>
