<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dee3dzihr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dee3dzihr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:clipboard-line" /></template>
