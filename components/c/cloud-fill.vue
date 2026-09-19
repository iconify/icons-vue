<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5h25bq-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="r5h25bq-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:cloud-fill" /></template>
