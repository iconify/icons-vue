<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nh6wr9bwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nh6wr9bwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:aas-shell-check-ok-filled" /></template>
