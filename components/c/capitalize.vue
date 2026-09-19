<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjuktpz5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rjuktpz5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:capitalize" /></template>
