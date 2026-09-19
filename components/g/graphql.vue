<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j313be5lq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j313be5lq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:graphql" /></template>
