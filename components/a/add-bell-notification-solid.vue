<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_nvcxbmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="w_nvcxbmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:add-bell-notification-solid" /></template>
