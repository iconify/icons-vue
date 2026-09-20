<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6jc6qbnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q6jc6qbnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:bootstrap" /></template>
