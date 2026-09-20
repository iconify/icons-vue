<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ulp9kbc7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ulp9kbc7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:lock-circle-outline" /></template>
