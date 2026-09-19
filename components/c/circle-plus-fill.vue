<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/btsr7ablu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="btsr7ablu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:circle-plus-fill" /></template>
