<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/umchrmbvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="umchrmbvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:clock-10-filled" /></template>
