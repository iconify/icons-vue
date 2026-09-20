<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e552mfb4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e552mfb4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:generic-device-success" /></template>
