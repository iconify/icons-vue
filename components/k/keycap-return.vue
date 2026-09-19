<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a3ed7nb8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="a3ed7nb8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:keycap-return" /></template>
