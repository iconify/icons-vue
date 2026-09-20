<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_-r47b4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="w_-r47b4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:chevrons-square-down" /></template>
