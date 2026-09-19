<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/je-u0bcmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="je-u0bcmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:hare" /></template>
