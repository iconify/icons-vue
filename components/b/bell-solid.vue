<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fd_488hbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fd_488hbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:bell-solid" /></template>
