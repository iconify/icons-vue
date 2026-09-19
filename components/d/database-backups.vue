<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sdh1wltpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sdh1wltpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:database-backups" /></template>
