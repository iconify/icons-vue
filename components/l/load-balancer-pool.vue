<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bzfby6bzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bzfby6bzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:load-balancer-pool" /></template>
