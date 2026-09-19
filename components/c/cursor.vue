<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vr85l6q2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vr85l6q2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:cursor" /></template>
