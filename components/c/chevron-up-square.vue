<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/foesq3whf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="foesq3whf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:chevron-up-square" /></template>
