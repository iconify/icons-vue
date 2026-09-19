<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m7dx4lb0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m7dx4lb0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:chart-bar-square-up-filled" /></template>
