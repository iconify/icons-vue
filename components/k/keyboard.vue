<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_za0_bbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i_za0_bbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:keyboard" /></template>
