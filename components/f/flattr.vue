<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbt9z6wse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cbt9z6wse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:flattr" /></template>
