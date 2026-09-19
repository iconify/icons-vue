<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qe894tblh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qe894tblh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:arrow-align-v" /></template>
