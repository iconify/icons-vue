<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7d2p-b0v.css';
import '../../css/m/mp5nlkbxv.css';
import '../../css/z/zupd9frtd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p7d2p-b0v"/><path class="mp5nlkbxv"/><path class="zupd9frtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:file" /></template>
