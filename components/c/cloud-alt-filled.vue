<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnrr2voyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rnrr2voyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cloud-alt-filled" /></template>
