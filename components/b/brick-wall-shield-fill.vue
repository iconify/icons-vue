<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qtv6bpb9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qtv6bpb9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:brick-wall-shield-fill" /></template>
