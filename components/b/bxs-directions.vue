<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tgfm8ab9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tgfm8ab9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-directions" /></template>
