<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-1fa5hld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a-1fa5hld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:cloud-heart" /></template>
