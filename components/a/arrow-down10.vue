<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xfnwd7b7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xfnwd7b7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:arrow-down10" /></template>
