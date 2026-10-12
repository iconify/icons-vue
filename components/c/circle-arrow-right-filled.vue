<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uy0h67bbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uy0h67bbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:circle-arrow-right-filled" /></template>
