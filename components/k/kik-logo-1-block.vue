<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vi4ts5bql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vi4ts5bql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:kik-logo-1-block" /></template>
