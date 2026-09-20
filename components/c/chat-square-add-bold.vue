<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jgxvx1b8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jgxvx1b8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-square-add-bold" /></template>
