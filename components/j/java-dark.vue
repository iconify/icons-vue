<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sx9w5c09m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sx9w5c09m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:java-dark" /></template>
