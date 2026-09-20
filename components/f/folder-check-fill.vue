<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/po70vxbpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="po70vxbpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:folder-check-fill" /></template>
