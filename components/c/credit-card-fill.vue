<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-x-aztdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f-x-aztdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:credit-card-fill" /></template>
