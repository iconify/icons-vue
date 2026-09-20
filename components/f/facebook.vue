<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yx9ipob0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yx9ipob0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:facebook" /></template>
