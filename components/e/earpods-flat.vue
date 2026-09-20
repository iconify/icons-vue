<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/au9804-ug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="au9804-ug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:earpods-flat" /></template>
