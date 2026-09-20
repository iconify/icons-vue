<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yh5wx3b2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yh5wx3b2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:klm" /></template>
