<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vzu302yje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vzu302yje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:currency-cny-fill" /></template>
