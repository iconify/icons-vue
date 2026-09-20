<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rrd3bnp0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rrd3bnp0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:bower-logo-block" /></template>
