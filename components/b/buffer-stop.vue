<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xyc9zmnvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xyc9zmnvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:buffer-stop" /></template>
