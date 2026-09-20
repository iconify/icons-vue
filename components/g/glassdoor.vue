<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/urr_ni9ue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="urr_ni9ue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:glassdoor" /></template>
