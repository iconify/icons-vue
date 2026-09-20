<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-0emdb2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j-0emdb2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:billboard" /></template>
