<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wm_vhljjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wm_vhljjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:lens" /></template>
