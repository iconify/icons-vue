<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-e5l_3bn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w-e5l_3bn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-vertical-center" /></template>
