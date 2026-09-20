<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8ubvfbil.css';
import '../../css/u/uyme-uvxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f8ubvfbil ouiIcon__fillSecondary"/><path class="uyme-uvxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:app-discover" /></template>
