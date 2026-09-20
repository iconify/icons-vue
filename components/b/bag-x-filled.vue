<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixboce-cq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ixboce-cq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bag-x-filled" /></template>
