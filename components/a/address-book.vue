<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bj8kg5b4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="bj8kg5b4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:address-book" /></template>
