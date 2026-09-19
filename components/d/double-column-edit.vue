<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ntg6q2s3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ntg6q2s3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:double-column-edit" /></template>
