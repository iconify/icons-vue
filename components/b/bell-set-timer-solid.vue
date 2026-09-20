<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zju57bchu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zju57bchu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:bell-set-timer-solid" /></template>
