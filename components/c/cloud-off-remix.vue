<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zk_c1n3dh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zk_c1n3dh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:cloud-off-remix" /></template>
