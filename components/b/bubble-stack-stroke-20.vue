<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpfsank0h.css';
import '../../css/u/uedqdgfhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lpfsank0h"/><path class="uedqdgfhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:bubble-stack-stroke-20" /></template>
