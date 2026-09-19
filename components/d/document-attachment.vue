<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eq7h70pom.css';
import '../../css/y/y3ymk3bab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="eq7h70pom"/><path class="y3ymk3bab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:document-attachment" /></template>
