<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_mg4gbeq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a_mg4gbeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:finger-up" /></template>
