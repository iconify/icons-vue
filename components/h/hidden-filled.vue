<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xgzkv4bov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xgzkv4bov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:hidden-filled" /></template>
