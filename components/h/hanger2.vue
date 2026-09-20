<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/svjjnlb5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="svjjnlb5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:hanger2" /></template>
