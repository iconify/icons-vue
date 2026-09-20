<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zp2p8cbjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zp2p8cbjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:folder-kanban-bold" /></template>
