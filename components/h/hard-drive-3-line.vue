<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oud9o5bru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oud9o5bru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:hard-drive-3-line" /></template>
