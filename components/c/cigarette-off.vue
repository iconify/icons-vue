<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fav1lfbxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fav1lfbxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:cigarette-off" /></template>
