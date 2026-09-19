<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pj4fatbiu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="pj4fatbiu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:h-expand" /></template>
