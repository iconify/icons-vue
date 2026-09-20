<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tjjklxbvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="tjjklxbvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:cargobike-under-list-beside-checkmark" /></template>
