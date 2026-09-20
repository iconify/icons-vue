<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djuy7yu_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="djuy7yu_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:hive-blockchain" /></template>
