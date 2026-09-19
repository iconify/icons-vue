<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a81gz4b4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="a81gz4b4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:follow-user" /></template>
