<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7cpylcvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w7cpylcvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:chat-alt-add-fill" /></template>
