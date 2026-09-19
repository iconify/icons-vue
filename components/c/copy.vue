<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7mdh3bqy.css';
import '../../css/q/qvisowbeh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i7mdh3bqy"/><path class="qvisowbeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:copy" /></template>
