<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2n33h_gb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w2n33h_gb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:lucid" /></template>
