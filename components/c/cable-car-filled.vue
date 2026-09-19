<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5j33dbsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e5j33dbsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cable-car-filled" /></template>
