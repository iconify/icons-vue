<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/df0h_ihsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="df0h_ihsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:flame-filled" /></template>
