<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_sa4jb9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="e_sa4jb9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:hiker" /></template>
