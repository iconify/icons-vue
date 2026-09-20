<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oun0_yubu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oun0_yubu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:arrow-reply-light" /></template>
