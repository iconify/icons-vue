<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gek8pcbul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="gek8pcbul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:electric-light-bulb-filled" /></template>
