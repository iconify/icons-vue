<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3_3rlbpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="g3_3rlbpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:leftmost" /></template>
