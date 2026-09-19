<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cfnq0bbpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cfnq0bbpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:cloud-upload" /></template>
