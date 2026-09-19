<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dd0x-741h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="dd0x-741h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:location-fill" /></template>
