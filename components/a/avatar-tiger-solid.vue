<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vo_2k_dtv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vo_2k_dtv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-tiger-solid" /></template>
