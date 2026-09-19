<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o2s2eubjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o2s2eubjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:act" /></template>
