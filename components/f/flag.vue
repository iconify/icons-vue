<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzmqz21qp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="dzmqz21qp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:flag" /></template>
