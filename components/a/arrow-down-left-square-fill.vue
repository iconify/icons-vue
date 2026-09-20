<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7dlsnbjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d7dlsnbjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:arrow-down-left-square-fill" /></template>
