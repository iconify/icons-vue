<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx6f9ibwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jx6f9ibwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:credit-card" /></template>
