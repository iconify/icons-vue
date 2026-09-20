<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gex0890uz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gex0890uz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:hoppscotch" /></template>
