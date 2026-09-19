<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yycurmbem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yycurmbem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:list-setting" /></template>
