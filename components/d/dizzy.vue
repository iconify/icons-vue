<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hxkx06lzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="hxkx06lzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:dizzy" /></template>
