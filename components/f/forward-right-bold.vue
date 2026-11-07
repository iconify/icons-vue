<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipa3nybtl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ipa3nybtl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:forward-right-bold" /></template>
