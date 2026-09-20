<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tq6logb-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tq6logb-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:beszel-dark" /></template>
