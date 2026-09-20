<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zfh642bof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zfh642bof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-t-solid" /></template>
