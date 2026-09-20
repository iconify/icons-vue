<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qa4o83b8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qa4o83b8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:etsy" /></template>
