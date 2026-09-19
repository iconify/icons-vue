<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vk1f5g_bz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="vk1f5g_bz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:floppy-disk-small" /></template>
