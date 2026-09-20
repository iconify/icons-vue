<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xtugqvbcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xtugqvbcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:contract-down" /></template>
