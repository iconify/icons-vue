<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/db98s4ozf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":432};
const content = `<path class="db98s4ozf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:assignment-alert" /></template>
