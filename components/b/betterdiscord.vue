<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwkkcb_dj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fwkkcb_dj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:betterdiscord" /></template>
