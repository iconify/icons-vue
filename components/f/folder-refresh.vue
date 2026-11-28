<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft0cpxbvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ft0cpxbvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:folder-refresh" /></template>
