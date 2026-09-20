<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqudf_bri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iqudf_bri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:chalkboard-filled" /></template>
