<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi1kmp1ol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bi1kmp1ol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:chat" /></template>
