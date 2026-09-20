<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gv23j4gpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gv23j4gpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bus" /></template>
