<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-9656b-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f-9656b-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:facebook-messenger" /></template>
