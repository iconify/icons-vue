<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tywtcxb_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tywtcxb_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:bandage" /></template>
