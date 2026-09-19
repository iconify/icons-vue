<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ln7ya2bio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ln7ya2bio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:chevron-right-square-filled" /></template>
