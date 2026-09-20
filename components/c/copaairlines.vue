<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wc722rblm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wc722rblm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:copaairlines" /></template>
