<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lm4xawukx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lm4xawukx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:lock" /></template>
