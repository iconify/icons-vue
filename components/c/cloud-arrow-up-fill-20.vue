<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-x5p8uzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="p-x5p8uzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:cloud-arrow-up-fill-20" /></template>
