<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aaol0eb1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="aaol0eb1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:houzz" /></template>
