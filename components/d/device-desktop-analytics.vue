<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h58-a_tnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h58-a_tnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-desktop-analytics" /></template>
