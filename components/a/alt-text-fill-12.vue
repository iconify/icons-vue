<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3kc6x8kr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="g3kc6x8kr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:alt-text-fill-12" /></template>
