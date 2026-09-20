<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5pc01b5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q5pc01b5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:glasses-2-line" /></template>
