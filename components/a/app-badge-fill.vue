<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a3b5a86vl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="a3b5a86vl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:app-badge-fill" /></template>
