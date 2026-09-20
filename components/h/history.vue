<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pnxhovbed.css';
import '../../css/o/o5bl2wrlr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pnxhovbed"/><path class="o5bl2wrlr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:history" /></template>
