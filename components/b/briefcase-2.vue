<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3war6ylu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="s3war6ylu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:briefcase-2" /></template>
