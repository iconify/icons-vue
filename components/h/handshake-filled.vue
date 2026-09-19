<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yxjj8npel.css';
import '../../css/l/l2afcqtvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yxjj8npel"/><path class="l2afcqtvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:handshake-filled" /></template>
