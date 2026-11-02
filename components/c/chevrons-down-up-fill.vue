<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ra3w6pbok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ra3w6pbok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chevrons-down-up-fill" /></template>
