<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wiycw97dq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wiycw97dq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:google-pixel" /></template>
