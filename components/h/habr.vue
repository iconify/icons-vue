<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/diqq20_5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="diqq20_5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:habr" /></template>
