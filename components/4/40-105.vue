<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kniyv1net.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":528,"height":448};
const content = `<path class="kniyv1net"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:40-105" /></template>
