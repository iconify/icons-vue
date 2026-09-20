<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/idk8i0bvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="idk8i0bvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:folder-network" /></template>
