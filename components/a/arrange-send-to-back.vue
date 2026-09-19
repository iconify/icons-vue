<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4k_rceqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="v4k_rceqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:arrange-send-to-back" /></template>
