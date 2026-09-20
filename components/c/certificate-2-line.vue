<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b7zqifb6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b7zqifb6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:certificate-2-line" /></template>
