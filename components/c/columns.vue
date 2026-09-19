<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yetb_qhpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yetb_qhpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:columns" /></template>
