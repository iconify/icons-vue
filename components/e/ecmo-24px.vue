<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqe610a-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zqe610a-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:ecmo-24px" /></template>
