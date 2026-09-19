<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q20rrzbfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q20rrzbfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:arrow-down-outline" /></template>
