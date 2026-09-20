<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kega9ac9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kega9ac9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:airline-seat-recline-extra" /></template>
