<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdaswzbvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="pdaswzbvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:chevron-up" /></template>
