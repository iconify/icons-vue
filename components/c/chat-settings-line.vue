<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/to9c7bclz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="to9c7bclz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:chat-settings-line" /></template>
