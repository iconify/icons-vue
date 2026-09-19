<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fnr30o6lz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="fnr30o6lz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:file-alt" /></template>
