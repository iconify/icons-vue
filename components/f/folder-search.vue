<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhr9m9bvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vhr9m9bvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:folder-search" /></template>
