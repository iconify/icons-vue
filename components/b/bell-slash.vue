<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t9u6-ybaa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t9u6-ybaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:bell-slash" /></template>
