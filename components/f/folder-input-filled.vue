<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ntu5cfbty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ntu5cfbty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:folder-input-filled" /></template>
