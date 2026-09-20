<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0evnobiw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="e0evnobiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:external" /></template>
