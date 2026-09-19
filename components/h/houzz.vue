<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n7lo-eued.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n7lo-eued"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:houzz" /></template>
