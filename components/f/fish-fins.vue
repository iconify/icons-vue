<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4fj89t1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="q4fj89t1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:fish-fins" /></template>
