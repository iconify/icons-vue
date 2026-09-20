<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfqzcrbba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rfqzcrbba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:equal-approximately-not" /></template>
