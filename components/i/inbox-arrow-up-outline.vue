<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rc1h2ybiu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rc1h2ybiu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:inbox-arrow-up-outline" /></template>
