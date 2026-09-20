<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wu40zcctt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wu40zcctt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:arrow-long-up-left" /></template>
