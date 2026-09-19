<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1j49ptmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="y1j49ptmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:language-cyrillic" /></template>
