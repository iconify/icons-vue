<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mk8n6vbra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mk8n6vbra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:car-taxi-front" /></template>
