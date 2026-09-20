<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iu47f4b-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="iu47f4b-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:alert" /></template>
