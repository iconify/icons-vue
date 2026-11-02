<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5qu6z45s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e5qu6z45s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:arrow-up-circle-line" /></template>
