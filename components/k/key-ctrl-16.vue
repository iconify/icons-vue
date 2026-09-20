<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/an1_8sz0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="an1_8sz0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:key-ctrl-16" /></template>
