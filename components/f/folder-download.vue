<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gw1cj-brk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gw1cj-brk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:folder-download" /></template>
