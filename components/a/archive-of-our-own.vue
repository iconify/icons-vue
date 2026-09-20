<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxfhqtdxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xxfhqtdxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:archive-of-our-own" /></template>
