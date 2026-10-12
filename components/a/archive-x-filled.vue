<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytun2xkkw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ytun2xkkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:archive-x-filled" /></template>
