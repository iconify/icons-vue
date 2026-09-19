<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qm1-5mbwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="qm1-5mbwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:cloud-weather" /></template>
