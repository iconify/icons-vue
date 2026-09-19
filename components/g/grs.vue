<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ysdpklb7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ysdpklb7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:grs" /></template>
