<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpkwi3bmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tpkwi3bmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:label-folder-tag-remix" /></template>
