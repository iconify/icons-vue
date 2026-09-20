<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xf52njb4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xf52njb4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-v-diamond-solid" /></template>
