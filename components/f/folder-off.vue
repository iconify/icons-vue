<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gnu7jpalj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gnu7jpalj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:folder-off" /></template>
