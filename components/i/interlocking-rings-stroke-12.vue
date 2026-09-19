<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gehy3pb4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="gehy3pb4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:interlocking-rings-stroke-12" /></template>
