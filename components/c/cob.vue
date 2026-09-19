<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/blna_7e-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="blna_7e-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:cob" /></template>
