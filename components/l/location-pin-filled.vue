<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qvp_25qpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="qvp_25qpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:location-pin-filled" /></template>
