<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vxqn-s10j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vxqn-s10j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:etihad-airways" /></template>
