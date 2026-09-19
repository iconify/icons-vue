<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2r06bb8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q2r06bb8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:linkedin-in" /></template>
