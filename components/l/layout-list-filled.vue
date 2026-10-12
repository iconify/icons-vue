<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wr_-ibcyq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wr_-ibcyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:layout-list-filled" /></template>
