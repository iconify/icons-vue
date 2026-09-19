<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxfil_d2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zxfil_d2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:chat-alt" /></template>
