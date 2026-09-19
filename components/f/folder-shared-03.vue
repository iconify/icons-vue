<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqymmtbfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hqymmtbfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:folder-shared-03" /></template>
