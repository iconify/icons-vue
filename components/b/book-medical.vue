<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdhe4kbnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="gdhe4kbnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:book-medical" /></template>
