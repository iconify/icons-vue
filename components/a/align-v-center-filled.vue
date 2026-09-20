<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6cnv5qul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y6cnv5qul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:align-v-center-filled" /></template>
