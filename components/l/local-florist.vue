<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vphlp94-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":456};
const content = `<path class="vphlp94-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:local-florist" /></template>
