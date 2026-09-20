<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pt4fctb7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pt4fctb7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:chat-alt-3-fill" /></template>
