<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w36_7vbsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w36_7vbsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bath-outline" /></template>
