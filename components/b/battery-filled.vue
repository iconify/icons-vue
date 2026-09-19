<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xobw0_9rr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xobw0_9rr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:battery-filled" /></template>
