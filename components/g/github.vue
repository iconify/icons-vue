<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rs8zk6bka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rs8zk6bka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:github" /></template>
