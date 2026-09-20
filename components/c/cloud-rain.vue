<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezso3g27z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ezso3g27z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:cloud-rain" /></template>
