<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dfy61-bkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dfy61-bkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:columns-3-outline" /></template>
