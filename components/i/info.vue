<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t48yxwfsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t48yxwfsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:info" /></template>
