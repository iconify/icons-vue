<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jg34fmb8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jg34fmb8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:lr-defender" /></template>
