<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cek6ewbqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":40,"height":40};
const content = `<path class="cek6ewbqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iwwa:add" /></template>
