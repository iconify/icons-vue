<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7b62qu9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e7b62qu9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:blogger" /></template>
