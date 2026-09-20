<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uc24q9xfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uc24q9xfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:hashicorp" /></template>
