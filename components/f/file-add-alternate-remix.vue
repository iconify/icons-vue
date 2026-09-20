<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wu9tx1bnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="wu9tx1bnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:file-add-alternate-remix" /></template>
