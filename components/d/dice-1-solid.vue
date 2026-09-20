<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k99vk2bjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k99vk2bjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:dice-1-solid" /></template>
