<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-nf9pbgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="h-nf9pbgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:align-right-20" /></template>
