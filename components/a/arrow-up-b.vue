<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8r1af9ja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m8r1af9ja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:arrow-up-b" /></template>
