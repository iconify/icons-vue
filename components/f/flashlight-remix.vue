<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/htkea5bor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="htkea5bor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:flashlight-remix" /></template>
