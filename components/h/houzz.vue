<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nap9lkbmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nap9lkbmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:houzz" /></template>
