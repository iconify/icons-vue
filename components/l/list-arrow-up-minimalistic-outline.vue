<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kc83huhip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kc83huhip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:list-arrow-up-minimalistic-outline" /></template>
