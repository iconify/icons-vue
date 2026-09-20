<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ldch-ca-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ldch-ca-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:board-remix" /></template>
