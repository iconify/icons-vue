<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdydk6bsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="bdydk6bsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:erlang" /></template>
