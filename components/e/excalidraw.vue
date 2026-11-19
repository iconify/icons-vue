<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tiu53obws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="tiu53obws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:excalidraw" /></template>
