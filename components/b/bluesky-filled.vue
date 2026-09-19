<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7g2yjbil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v7g2yjbil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:bluesky-filled" /></template>
