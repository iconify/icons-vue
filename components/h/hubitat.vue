<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qw9c-cb4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qw9c-cb4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:hubitat" /></template>
