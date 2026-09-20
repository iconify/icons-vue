<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/loo_9-4ps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="loo_9-4ps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:json" /></template>
