<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwsfkogjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mwsfkogjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:chat-plus" /></template>
