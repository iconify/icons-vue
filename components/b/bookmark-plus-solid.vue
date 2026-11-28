<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/feumftmof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="feumftmof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:bookmark-plus-solid" /></template>
