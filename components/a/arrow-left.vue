<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abx2bebyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":448};
const content = `<path class="abx2bebyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:arrow-left" /></template>
