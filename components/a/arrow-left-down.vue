<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whuoxvb_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="whuoxvb_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:arrow-left-down" /></template>
