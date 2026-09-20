<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxl0p-bhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kxl0p-bhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:call-filled" /></template>
