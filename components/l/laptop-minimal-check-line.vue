<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/go0c73cns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="go0c73cns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:laptop-minimal-check-line" /></template>
