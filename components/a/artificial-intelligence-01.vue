<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wsq8muggl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wsq8muggl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:artificial-intelligence-01" /></template>
