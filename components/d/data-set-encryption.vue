<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o1ko_g8nw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o1ko_g8nw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:data-set-encryption" /></template>
