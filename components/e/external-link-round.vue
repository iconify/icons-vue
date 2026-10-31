<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sg9ftubme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sg9ftubme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:external-link-round" /></template>
