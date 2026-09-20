<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fu5cqxbmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path clip-rule="evenodd" class="fu5cqxbmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:chevron-up-12" /></template>
