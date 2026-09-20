<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/brbl73iqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="brbl73iqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:align-end-vertical" /></template>
