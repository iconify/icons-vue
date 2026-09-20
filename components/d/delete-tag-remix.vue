<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2z_ejenp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="l2z_ejenp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:delete-tag-remix" /></template>
