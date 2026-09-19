<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dd7cgg0ex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":24};
const content = `<path class="dd7cgg0ex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:headphone" /></template>
