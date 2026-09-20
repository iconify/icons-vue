<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xfqzb-bwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xfqzb-bwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:dunked" /></template>
