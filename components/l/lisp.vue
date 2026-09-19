<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jr10uwbnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jr10uwbnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:lisp" /></template>
