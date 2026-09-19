<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jztbvhf1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="jztbvhf1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:file-audio" /></template>
