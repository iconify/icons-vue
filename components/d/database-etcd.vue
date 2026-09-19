<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tdqj4ciwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tdqj4ciwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:database-etcd" /></template>
