<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m4tooib-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path class="m4tooib-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="brandico:instagram" /></template>
