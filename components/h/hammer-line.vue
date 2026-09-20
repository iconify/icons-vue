<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izu86rbqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="izu86rbqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:hammer-line" /></template>
