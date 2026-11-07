<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmh9szrbi.css';
import '../../css/g/gmic3ry4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cmh9szrbi"/><path class="gmic3ry4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-left-to-line-outline" /></template>
