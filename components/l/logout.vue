<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmvf2-mgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="gmvf2-mgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:logout" /></template>
