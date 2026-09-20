<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eb5cvdbag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eb5cvdbag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:generic-device-synchronized" /></template>
