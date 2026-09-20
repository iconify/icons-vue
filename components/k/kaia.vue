<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrmg7_fcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wrmg7_fcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:kaia" /></template>
