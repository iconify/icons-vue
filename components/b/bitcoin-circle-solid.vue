<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2ll2kbqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q2ll2kbqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:bitcoin-circle-solid" /></template>
