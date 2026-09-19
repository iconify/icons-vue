<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jdu8ew18m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":960};
const content = `<path class="jdu8ew18m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:film" /></template>
