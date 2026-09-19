<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kl2e97jtx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kl2e97jtx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:infinity" /></template>
