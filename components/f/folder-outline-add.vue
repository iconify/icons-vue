<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ahz_e6bni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ahz_e6bni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:folder-outline-add" /></template>
