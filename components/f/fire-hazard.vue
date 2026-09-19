<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1qja4bht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x1qja4bht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:fire-hazard" /></template>
