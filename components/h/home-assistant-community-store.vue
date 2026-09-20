<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s28g0abgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s28g0abgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:home-assistant-community-store" /></template>
