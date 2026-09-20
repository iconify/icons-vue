<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wuwgo473d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wuwgo473d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:arrange-letter" /></template>
