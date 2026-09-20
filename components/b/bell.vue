<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/un83tfh1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="un83tfh1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bell" /></template>
