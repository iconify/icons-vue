<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h30shkbsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="h30shkbsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:dots-2x3-20-solid" /></template>
