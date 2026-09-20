<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kz31hdzhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="kz31hdzhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:checkboxes-empty-filled" /></template>
