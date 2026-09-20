<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sz9xce7wc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sz9xce7wc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:goodreads" /></template>
