<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/os--etbpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="os--etbpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:ghostery" /></template>
