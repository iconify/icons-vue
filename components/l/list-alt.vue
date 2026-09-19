<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydtkrsc2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="ydtkrsc2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:list-alt" /></template>
