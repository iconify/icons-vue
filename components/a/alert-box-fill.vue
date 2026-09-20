<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ye9hi3bxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="ye9hi3bxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:alert-box-fill" /></template>
