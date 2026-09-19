<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yft_2jb0w.css';
import '../../css/i/iwsz-9ben.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yft_2jb0w"/><path class="iwsz-9ben"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:copy-list-filled" /></template>
