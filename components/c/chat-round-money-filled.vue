<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvlfz5cod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cvlfz5cod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:chat-round-money-filled" /></template>
