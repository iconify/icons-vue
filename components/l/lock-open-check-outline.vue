<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zpkjnpb3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zpkjnpb3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:lock-open-check-outline" /></template>
