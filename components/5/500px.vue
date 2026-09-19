<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p02trow8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":19,"height":24};
const content = `<path class="p02trow8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:500px" /></template>
