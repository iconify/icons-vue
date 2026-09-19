<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c17kk1-8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="c17kk1-8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:joystick" /></template>
