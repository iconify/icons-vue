<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/or-6ds2_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="or-6ds2_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:airplay-video" /></template>
