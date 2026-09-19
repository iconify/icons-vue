<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtc4babzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jtc4babzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:file-music-outline" /></template>
