<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mx6s3u3tk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mx6s3u3tk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-chalkboard" /></template>
