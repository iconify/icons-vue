<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/loc77xbtr.css';
import '../../css/d/d0ipc7b7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="loc77xbtr"/><path class="d0ipc7b7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:brg" /></template>
