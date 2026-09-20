<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cfxt7qqpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cfxt7qqpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:certificate-solid" /></template>
