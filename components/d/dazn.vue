<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6-ju_xjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b6-ju_xjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:dazn" /></template>
