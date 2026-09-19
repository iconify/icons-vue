<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kcxg7mqrc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kcxg7mqrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:assignment-action-usage" /></template>
