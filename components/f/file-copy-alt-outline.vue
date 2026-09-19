<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ux5dqullz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ux5dqullz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:file-copy-alt-outline" /></template>
