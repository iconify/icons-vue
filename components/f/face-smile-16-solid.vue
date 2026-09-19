<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ec21vyzpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ec21vyzpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:face-smile-16-solid" /></template>
