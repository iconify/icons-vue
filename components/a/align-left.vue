<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tnhyq8uca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tnhyq8uca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:align-left" /></template>
