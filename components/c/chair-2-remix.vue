<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bj937vb0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bj937vb0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:chair-2-remix" /></template>
