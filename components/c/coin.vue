<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jsohd1-ty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jsohd1-ty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:coin" /></template>
