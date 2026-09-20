<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9jmw3b1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="o9jmw3b1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:hammer" /></template>
