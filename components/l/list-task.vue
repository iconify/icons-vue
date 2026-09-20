<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wisszls_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="wisszls_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:list-task" /></template>
