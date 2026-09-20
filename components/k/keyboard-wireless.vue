<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5a-otaph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f5a-otaph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:keyboard-wireless" /></template>
