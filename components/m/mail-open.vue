<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wsuqk849p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wsuqk849p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:mail-open" /></template>
