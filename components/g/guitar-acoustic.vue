<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/at68bwbkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="at68bwbkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:guitar-acoustic" /></template>
