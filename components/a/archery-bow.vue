<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zm785bl5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zm785bl5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:archery-bow" /></template>
