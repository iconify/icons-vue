<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nqyykw1dq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nqyykw1dq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:brightness-3" /></template>
