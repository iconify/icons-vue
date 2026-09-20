<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e83fdyu4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e83fdyu4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-compress-left" /></template>
