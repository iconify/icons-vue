<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wz0xl4pup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wz0xl4pup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:elastic-logstash-logo-block" /></template>
