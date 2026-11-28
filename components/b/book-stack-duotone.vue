<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fc3st3bkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fc3st3bkj primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:book-stack-duotone" /></template>
