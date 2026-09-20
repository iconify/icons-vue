<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oekeczbjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oekeczbjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bridge-2-fill" /></template>
