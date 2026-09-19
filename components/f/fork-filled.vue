<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fso1x3bbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fso1x3bbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:fork-filled" /></template>
