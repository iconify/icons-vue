<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3j9tjmxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="y3j9tjmxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:eql" /></template>
