<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/od1wn8bny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="od1wn8bny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:folder-add-bold" /></template>
