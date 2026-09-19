<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qkk-kyy9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qkk-kyy9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:apache-airflow" /></template>
