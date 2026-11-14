<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7-upabru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t7-upabru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:cloud-server" /></template>
