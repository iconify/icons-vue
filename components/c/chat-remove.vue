<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ykvyq4wpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ykvyq4wpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:chat-remove" /></template>
