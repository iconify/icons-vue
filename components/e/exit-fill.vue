<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vk5xc535u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vk5xc535u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:exit-fill" /></template>
