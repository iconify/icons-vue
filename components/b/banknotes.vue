<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbj3n7r_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="zbj3n7r_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:banknotes" /></template>
