<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ehtfmd7by.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ehtfmd7by"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:keyboard-asterisk-1-bold" /></template>
