<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rqqc-fdfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rqqc-fdfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:grid4-filled" /></template>
