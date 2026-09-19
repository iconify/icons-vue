<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8t325kav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="b8t325kav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:earth-america-o" /></template>
