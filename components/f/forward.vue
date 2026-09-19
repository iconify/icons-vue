<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lj3enubxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":472};
const content = `<path class="lj3enubxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:forward" /></template>
