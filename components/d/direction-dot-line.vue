<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8ussty6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t8ussty6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:direction-dot-line" /></template>
