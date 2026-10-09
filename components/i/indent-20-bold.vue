<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2z7ddc-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="v2z7ddc-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:indent-20-bold" /></template>
