<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3kl3w7lm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e3kl3w7lm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:magnet-down" /></template>
