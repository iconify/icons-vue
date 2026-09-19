<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ha6s8epuq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ha6s8epuq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-folder" /></template>
