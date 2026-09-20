<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/klqnr0qpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="klqnr0qpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:chat-text-fill" /></template>
