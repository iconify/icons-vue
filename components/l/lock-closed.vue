<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wtlog_bvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wtlog_bvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:lock-closed" /></template>
