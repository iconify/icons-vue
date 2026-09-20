<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vse5ibbpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vse5ibbpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:folder-transfer" /></template>
