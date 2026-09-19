<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmr9r7v8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1792};
const content = `<path class="jmr9r7v8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:envelope-open-o" /></template>
