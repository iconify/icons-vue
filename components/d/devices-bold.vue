<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9benlbfz.css';
import '../../css/k/kemsso1tv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e9benlbfz"/><path clip-rule="evenodd" class="kemsso1tv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:devices-bold" /></template>
