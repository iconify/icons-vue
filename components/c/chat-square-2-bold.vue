<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/okcwy630f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="okcwy630f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-square-2-bold" /></template>
