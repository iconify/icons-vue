<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kogkj5uzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kogkj5uzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:google-maps-logo-block" /></template>
