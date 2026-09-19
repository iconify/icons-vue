<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3s5ci-4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="n3s5ci-4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:dish-dot" /></template>
