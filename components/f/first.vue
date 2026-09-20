<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pch8ymubu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pch8ymubu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:first" /></template>
