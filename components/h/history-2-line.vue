<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-o6yib2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r-o6yib2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:history-2-line" /></template>
