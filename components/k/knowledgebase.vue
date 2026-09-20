<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ei2jpv_jy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ei2jpv_jy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:knowledgebase" /></template>
