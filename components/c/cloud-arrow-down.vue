<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqtuzr9cv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cqtuzr9cv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:cloud-arrow-down" /></template>
