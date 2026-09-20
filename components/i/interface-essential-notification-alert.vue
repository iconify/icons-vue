<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pno3q_b-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pno3q_b-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-notification-alert" /></template>
