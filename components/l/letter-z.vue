<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ec9i80skt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ec9i80skt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-z" /></template>
