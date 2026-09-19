<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipefi82fx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ipefi82fx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ikea-risbyn" /></template>
