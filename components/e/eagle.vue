<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dqdkc20cg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dqdkc20cg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:eagle" /></template>
