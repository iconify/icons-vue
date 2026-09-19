<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a3e2ddq-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a3e2ddq-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:continuous-deployment" /></template>
