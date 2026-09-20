<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ni66x6cvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ni66x6cvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:heroku" /></template>
