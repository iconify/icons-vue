<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmt9_z-xl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qmt9_z-xl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:discord-logo-2-block" /></template>
