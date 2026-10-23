<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fgcxa8y2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fgcxa8y2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:japanese-yen" /></template>
