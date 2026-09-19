<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tb_j-j7cs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tb_j-j7cs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:concierge-bell-filled" /></template>
