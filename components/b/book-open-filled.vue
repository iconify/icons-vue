<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e49gq2bot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e49gq2bot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:book-open-filled" /></template>
