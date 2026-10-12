<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdxjy7b8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gdxjy7b8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:css-fill-20" /></template>
