<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zm7raibzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="zm7raibzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrowtriangle-down-square-fill" /></template>
