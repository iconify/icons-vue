<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/baai45q_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="baai45q_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:direction-fork" /></template>
