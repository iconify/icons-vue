<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vnw-_ac5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vnw-_ac5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:degoog-dark" /></template>
