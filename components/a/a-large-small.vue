<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sq_6aabuw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sq_6aabuw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:a-large-small" /></template>
