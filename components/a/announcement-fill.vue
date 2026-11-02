<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ptqrfybfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ptqrfybfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:announcement-fill" /></template>
