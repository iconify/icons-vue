<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/de6jlgzhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="de6jlgzhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrowtriangle-left-square-fill" /></template>
