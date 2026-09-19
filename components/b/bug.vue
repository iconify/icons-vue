<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9_-o9owr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":496};
const content = `<path class="o9_-o9owr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:bug" /></template>
