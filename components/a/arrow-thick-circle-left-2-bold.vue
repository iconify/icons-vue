<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eupidrbxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eupidrbxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:arrow-thick-circle-left-2-bold" /></template>
