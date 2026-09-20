<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pp1n6kbii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pp1n6kbii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:checkbox-blank-off" /></template>
