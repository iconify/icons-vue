<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lrah4su8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lrah4su8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:discussion-minus" /></template>
