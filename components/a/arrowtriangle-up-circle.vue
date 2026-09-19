<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gz4zuhgej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="gz4zuhgej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrowtriangle-up-circle" /></template>
