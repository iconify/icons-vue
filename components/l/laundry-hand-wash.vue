<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yg3njrbjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yg3njrbjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:laundry-hand-wash" /></template>
