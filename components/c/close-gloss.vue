<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a49hwjbch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a49hwjbch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:close-gloss" /></template>
