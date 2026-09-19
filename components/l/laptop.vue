<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ttgog_btk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ttgog_btk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:laptop" /></template>
