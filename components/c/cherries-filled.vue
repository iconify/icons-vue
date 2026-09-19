<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mp7dy1b-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="mp7dy1b-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:cherries-filled" /></template>
