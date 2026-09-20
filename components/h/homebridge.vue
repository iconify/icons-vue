<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwk4ow2yn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fwk4ow2yn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:homebridge" /></template>
