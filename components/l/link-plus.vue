<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g88n68bvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g88n68bvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:link-plus" /></template>
