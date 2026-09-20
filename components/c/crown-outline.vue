<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/os9ts92df.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="os9ts92df"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:crown-outline" /></template>
