<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sghe-8bgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sghe-8bgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:basketball-filled" /></template>
