<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oji5awbvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oji5awbvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:chevron-down-filled" /></template>
