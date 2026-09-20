<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-f7__cdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-f7__cdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:caravan-1" /></template>
