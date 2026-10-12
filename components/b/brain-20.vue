<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lyyw2ejbf.css';
import '../../css/c/cdzkw9bwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lyyw2ejbf"/><path class="cdzkw9bwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:brain-20" /></template>
