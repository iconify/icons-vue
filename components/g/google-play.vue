<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-e1x6brn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y-e1x6brn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:google-play" /></template>
