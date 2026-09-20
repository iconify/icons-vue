<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iw5agubmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iw5agubmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:ionos" /></template>
