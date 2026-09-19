<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqwe795ej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iqwe795ej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:castbox" /></template>
