<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bstp5j7nw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="bstp5j7nw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:arrow-left" /></template>
