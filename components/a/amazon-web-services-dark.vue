<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dnia1ubeb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dnia1ubeb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:amazon-web-services-dark" /></template>
