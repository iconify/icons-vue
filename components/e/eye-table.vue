<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vkl8r-3at.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vkl8r-3at"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:eye-table" /></template>
