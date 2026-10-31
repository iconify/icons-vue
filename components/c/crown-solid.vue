<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uh0q379oy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uh0q379oy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:crown-solid" /></template>
