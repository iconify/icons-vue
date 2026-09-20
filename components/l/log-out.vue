<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqfdu9byr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kqfdu9byr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:log-out" /></template>
