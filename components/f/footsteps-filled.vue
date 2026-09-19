<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0otxgbxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s0otxgbxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:footsteps-filled" /></template>
