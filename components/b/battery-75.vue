<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_gu-l-pw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w_gu-l-pw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:battery-75" /></template>
