<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8pvc7bdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="h8pvc7bdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:fire-flame-curved" /></template>
