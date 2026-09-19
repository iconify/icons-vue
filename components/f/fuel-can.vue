<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ah8pjsbhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ah8pjsbhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:fuel-can" /></template>
