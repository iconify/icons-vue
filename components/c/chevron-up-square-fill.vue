<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-n7-wbdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w-n7-wbdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:chevron-up-square-fill" /></template>
