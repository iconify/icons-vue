<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3s14jg7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x3s14jg7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:dumbbell" /></template>
