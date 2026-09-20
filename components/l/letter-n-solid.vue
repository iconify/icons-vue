<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wfn6x6blk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wfn6x6blk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-n-solid" /></template>
