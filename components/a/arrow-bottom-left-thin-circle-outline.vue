<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzw8d4ipa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yzw8d4ipa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-bottom-left-thin-circle-outline" /></template>
