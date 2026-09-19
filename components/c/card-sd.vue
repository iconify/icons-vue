<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f963cdb6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":344,"height":432};
const content = `<path class="f963cdb6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:card-sd" /></template>
