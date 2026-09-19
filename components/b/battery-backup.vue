<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q605_cg2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q605_cg2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:battery-backup" /></template>
