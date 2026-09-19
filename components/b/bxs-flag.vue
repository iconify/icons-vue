<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iq1_qoxvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iq1_qoxvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-flag" /></template>
