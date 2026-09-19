<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/stifp2bza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="stifp2bza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:liver-alt-outline-24px" /></template>
