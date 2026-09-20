<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzj21sb8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mzj21sb8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:format-letter-starts-with" /></template>
