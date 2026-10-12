<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcacmsbyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vcacmsbyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:gallery-vertical-filled" /></template>
