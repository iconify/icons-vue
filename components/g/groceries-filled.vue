<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vyz221lmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vyz221lmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:groceries-filled" /></template>
