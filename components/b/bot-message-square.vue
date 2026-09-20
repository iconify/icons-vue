<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a9ae4_bfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a9ae4_bfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:bot-message-square" /></template>
