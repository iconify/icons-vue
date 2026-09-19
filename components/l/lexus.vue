<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv7ihhbsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hv7ihhbsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:lexus" /></template>
