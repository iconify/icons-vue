<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgewv6byr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":1536};
const content = `<path class="kgewv6byr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:drivers-license" /></template>
