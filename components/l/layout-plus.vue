<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j068h3bdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j068h3bdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:layout-plus" /></template>
