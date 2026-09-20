<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ehkfwkbvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ehkfwkbvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:compass-dashboard-light" /></template>
