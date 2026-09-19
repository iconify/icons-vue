<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/msgzh1bni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="msgzh1bni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:circle-arrow-out-up-left" /></template>
