<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvhf1p0al.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vvhf1p0al"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:delete-tag-remix" /></template>
