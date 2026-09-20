<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xeph6rbxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xeph6rbxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:figma-bold" /></template>
