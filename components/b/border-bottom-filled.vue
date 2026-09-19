<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cl5_it4ct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cl5_it4ct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:border-bottom-filled" /></template>
