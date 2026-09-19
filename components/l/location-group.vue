<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7y8ago1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="t7y8ago1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:location-group" /></template>
