<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmk613b2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zmk613b2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:giteeai" /></template>
