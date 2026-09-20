<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/duj4s1--s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="duj4s1--s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:ban" /></template>
