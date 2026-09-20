<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_ceh3bot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e_ceh3bot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:blood-bag-donation-remix" /></template>
