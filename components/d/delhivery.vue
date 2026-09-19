<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qvfg0bbjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qvfg0bbjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:delhivery" /></template>
