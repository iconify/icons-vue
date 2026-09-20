<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_n5z_b3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w_n5z_b3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:line-arrow-move-up-1-remix" /></template>
