<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j05aesb6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="j05aesb6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:feedback-response-solid" /></template>
