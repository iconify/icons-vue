<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sofh-7f6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sofh-7f6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chrome-fill" /></template>
