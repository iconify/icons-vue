<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cb-r98ulw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="cb-r98ulw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrowtriangle-left-circle-fill" /></template>
