<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sciqm6oqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sciqm6oqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:google-line" /></template>
