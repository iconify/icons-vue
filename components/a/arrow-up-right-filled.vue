<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tgfrq7b3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tgfrq7b3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-up-right-filled" /></template>
