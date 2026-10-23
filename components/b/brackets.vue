<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flg1lobzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="flg1lobzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:brackets" /></template>
