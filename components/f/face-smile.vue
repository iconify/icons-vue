<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rdbesbcce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="rdbesbcce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:face-smile" /></template>
