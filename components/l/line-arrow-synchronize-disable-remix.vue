<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ubp6vsclr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ubp6vsclr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:line-arrow-synchronize-disable-remix" /></template>
