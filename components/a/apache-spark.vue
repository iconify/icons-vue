<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sh3su9blv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sh3su9blv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:apache-spark" /></template>
