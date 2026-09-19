<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jotj3v2bz.css';
import '../../css/y/y_-ddrbdq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jotj3v2bz"/><path class="y_-ddrbdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-mailchimp" /></template>
