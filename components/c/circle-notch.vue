<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmq_q9baz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="kmq_q9baz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:circle-notch" /></template>
