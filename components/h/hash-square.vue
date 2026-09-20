<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rc7-p9bkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rc7-p9bkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:hash-square" /></template>
