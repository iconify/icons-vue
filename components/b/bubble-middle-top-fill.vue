<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hvpch3zpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="hvpch3zpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:bubble-middle-top-fill" /></template>
