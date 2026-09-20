<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e4ereq4fl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e4ereq4fl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:account-key" /></template>
