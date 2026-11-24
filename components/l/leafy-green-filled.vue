<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wsnt9mslf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wsnt9mslf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:leafy-green-filled" /></template>
