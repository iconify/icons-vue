<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l6smzk6xv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l6smzk6xv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:cake-remix" /></template>
