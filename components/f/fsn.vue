<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q1m-prfwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q1m-prfwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:fsn" /></template>
