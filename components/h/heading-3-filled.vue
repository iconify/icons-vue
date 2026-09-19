<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pg3b3wd3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pg3b3wd3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:heading-3-filled" /></template>
