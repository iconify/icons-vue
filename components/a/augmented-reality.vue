<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wiw1n4qap.css';
import '../../css/u/ugyrmsdwo.css';
import '../../css/t/ti3gn7b9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wiw1n4qap"/><circle class="ugyrmsdwo"/><path class="ti3gn7b9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:augmented-reality" /></template>
