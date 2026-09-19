<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_4gtvbxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="l_4gtvbxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:laravel-horizon" /></template>
