<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9fxnqbql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1696,"height":1600};
const content = `<path class="n9fxnqbql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:key" /></template>
