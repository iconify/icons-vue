<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rpodn9pqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rpodn9pqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:badge" /></template>
