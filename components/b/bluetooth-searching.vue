<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-8_t8frx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o-8_t8frx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:bluetooth-searching" /></template>
