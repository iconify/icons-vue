<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vkl5tz40n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="vkl5tz40n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:bread" /></template>
