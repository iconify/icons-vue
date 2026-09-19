<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mq-a3xwaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":528,"height":448};
const content = `<path class="mq-a3xwaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:60-140" /></template>
