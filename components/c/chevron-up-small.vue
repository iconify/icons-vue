<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eiup1veat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="eiup1veat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:chevron-up-small" /></template>
