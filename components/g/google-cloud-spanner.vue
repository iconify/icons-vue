<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/la8s9ccyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="la8s9ccyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:google-cloud-spanner" /></template>
