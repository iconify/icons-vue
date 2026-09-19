<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g97jdgv9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="g97jdgv9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:direction-bear-right-02" /></template>
