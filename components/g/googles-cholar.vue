<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/diidigbta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="diidigbta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:googles-cholar" /></template>
