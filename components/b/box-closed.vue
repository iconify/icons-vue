<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dl3uehkus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dl3uehkus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:box-closed" /></template>
