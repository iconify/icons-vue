<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rx4zlylhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rx4zlylhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:alert-fill" /></template>
