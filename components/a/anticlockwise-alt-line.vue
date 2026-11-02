<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvitscc-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tvitscc-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:anticlockwise-alt-line" /></template>
