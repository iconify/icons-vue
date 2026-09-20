<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/niph87b_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="niph87b_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:check-underline-circle" /></template>
