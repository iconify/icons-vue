<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/poltb9j9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":42};
const content = `<path class="poltb9j9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="topcoat:location" /></template>
