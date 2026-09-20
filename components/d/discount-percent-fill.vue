<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iz4r9rwwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iz4r9rwwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:discount-percent-fill" /></template>
