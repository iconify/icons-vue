<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gt030hb-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gt030hb-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:handshake" /></template>
