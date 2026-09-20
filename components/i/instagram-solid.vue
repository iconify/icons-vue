<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tb_uoqb2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tb_uoqb2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:instagram-solid" /></template>
