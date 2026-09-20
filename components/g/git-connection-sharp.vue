<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gj39tft-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gj39tft-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:git-connection-sharp" /></template>
