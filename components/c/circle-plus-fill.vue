<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/su6b2s4_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="su6b2s4_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:circle-plus-fill" /></template>
