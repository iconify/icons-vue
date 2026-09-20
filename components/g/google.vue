<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_kozdb7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p_kozdb7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:google" /></template>
