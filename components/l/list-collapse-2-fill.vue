<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xkvu_nbmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xkvu_nbmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:list-collapse-2-fill" /></template>
