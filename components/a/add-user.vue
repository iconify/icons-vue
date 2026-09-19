<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f310sub7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f310sub7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:add-user" /></template>
