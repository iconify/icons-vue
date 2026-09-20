<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a5v2pkban.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a5v2pkban"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:cookie" /></template>
