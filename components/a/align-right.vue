<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/girn4kpqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":448};
const content = `<path class="girn4kpqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:align-right" /></template>
