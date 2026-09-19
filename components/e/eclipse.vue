<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wbxx3n40q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="wbxx3n40q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:eclipse" /></template>
