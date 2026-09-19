<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p06ehhwsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="p06ehhwsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:chevron-double-down-20-solid" /></template>
