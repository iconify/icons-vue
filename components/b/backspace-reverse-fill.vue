<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxqpq861n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nxqpq861n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:backspace-reverse-fill" /></template>
