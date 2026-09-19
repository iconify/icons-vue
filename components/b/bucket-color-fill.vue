<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qd0mnx8hv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="qd0mnx8hv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:bucket-color-fill" /></template>
