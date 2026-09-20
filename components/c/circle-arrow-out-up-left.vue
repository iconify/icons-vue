<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5n-ojpms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c5n-ojpms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:circle-arrow-out-up-left" /></template>
