<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vsl0xbcpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vsl0xbcpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:building-4-fill" /></template>
