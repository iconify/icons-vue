<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3pn4uakb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="z3pn4uakb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:clipboard-list-fill-12" /></template>
