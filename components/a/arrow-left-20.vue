<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxyer0bvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cxyer0bvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:arrow-left-20" /></template>
