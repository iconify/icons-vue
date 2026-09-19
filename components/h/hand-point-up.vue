<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kehg7ij8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="kehg7ij8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:hand-point-up" /></template>
