<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2uofa4ka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c2uofa4ka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:bolt" /></template>
