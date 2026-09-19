<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h7oxfibsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":396,"height":512};
const content = `<path class="h7oxfibsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:cairo" /></template>
