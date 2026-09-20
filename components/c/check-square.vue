<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cidnmrdbv.css';
import '../../css/n/neifvedcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cidnmrdbv"/><path class="neifvedcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:check-square" /></template>
