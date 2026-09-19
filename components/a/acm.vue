<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ea9wp1b6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ea9wp1b6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:acm" /></template>
