<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/scum1rbwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="scum1rbwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:briefcase-medical" /></template>
