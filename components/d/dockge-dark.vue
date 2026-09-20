<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-odxj2go.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="g-odxj2go"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dockge-dark" /></template>
