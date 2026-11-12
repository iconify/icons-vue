<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx6xf8bug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jx6xf8bug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:building-x" /></template>
