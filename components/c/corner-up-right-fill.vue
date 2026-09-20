<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwqn_bbiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rwqn_bbiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:corner-up-right-fill" /></template>
