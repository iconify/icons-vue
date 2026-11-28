<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-mv1dshg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-mv1dshg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:book-solid" /></template>
