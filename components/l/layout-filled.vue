<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fd_d6heja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fd_d6heja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:layout-filled" /></template>
