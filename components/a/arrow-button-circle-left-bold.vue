<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bk-frvbab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bk-frvbab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:arrow-button-circle-left-bold" /></template>
