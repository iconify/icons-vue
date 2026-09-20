<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ozrfghbao.css';
import '../../css/h/h7g0yix5d.css';
import '../../css/v/v1jjnr7lu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ozrfghbao"/><path class="h7g0yix5d"/><path class="v1jjnr7lu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:cash" /></template>
