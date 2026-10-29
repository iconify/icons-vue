<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t5t95sj6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t5t95sj6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:command-solid" /></template>
