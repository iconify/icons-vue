<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/faue9jrht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="faue9jrht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:binding-connector" /></template>
