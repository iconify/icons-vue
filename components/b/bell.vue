<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7sk8owmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="d7sk8owmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:bell" /></template>
