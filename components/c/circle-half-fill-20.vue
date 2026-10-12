<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5_k3sbve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="z5_k3sbve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:circle-half-fill-20" /></template>
