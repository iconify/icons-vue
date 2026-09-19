<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_7ns1bko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t_7ns1bko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:campfires" /></template>
