<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iz7npyjda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iz7npyjda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:group-line" /></template>
