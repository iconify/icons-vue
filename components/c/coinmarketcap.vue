<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zb-aiqo9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zb-aiqo9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:coinmarketcap" /></template>
