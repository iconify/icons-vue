<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmmg8zb4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="kmmg8zb4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:add-favorite-fill" /></template>
