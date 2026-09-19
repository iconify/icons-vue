<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkrxt4bmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pkrxt4bmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-big-left-line-filled" /></template>
