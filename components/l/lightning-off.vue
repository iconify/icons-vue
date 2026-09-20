<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipxljsbzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ipxljsbzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:lightning-off" /></template>
