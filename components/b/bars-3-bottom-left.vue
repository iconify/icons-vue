<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lb6l9qbbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="lb6l9qbbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:bars-3-bottom-left" /></template>
