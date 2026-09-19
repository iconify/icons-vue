<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5luqjpur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x5luqjpur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:inbox" /></template>
