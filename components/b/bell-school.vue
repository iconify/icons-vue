<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vkgnl-x2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vkgnl-x2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:bell-school" /></template>
