<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flug27b3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="flug27b3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:alert-shield-filled" /></template>
