<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wt8yu95an.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wt8yu95an"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:kakaotalk" /></template>
