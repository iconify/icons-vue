<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z8-d1ab8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z8-d1ab8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-bookmark" /></template>
