<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t85jj0bln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t85jj0bln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-account-outline" /></template>
