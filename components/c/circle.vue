<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gcyzuk2ie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="gcyzuk2ie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:circle" /></template>
