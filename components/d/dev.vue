<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2px2_-ky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="q2px2_-ky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:dev" /></template>
