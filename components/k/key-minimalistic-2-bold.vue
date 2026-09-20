<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j2b3s_9dx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j2b3s_9dx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:key-minimalistic-2-bold" /></template>
