<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfnyhrbee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kfnyhrbee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bytesize:edit" /></template>
