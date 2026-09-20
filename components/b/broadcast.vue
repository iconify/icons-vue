<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/midos5b3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="midos5b3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:broadcast" /></template>
