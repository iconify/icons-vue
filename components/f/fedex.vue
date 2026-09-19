<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t46u2rhgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t46u2rhgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:fedex" /></template>
