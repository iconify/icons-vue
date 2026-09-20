<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdoh0m-2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pdoh0m-2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:color-tuning" /></template>
