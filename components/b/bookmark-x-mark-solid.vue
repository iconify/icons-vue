<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/az_l_5bsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="az_l_5bsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:bookmark-x-mark-solid" /></template>
