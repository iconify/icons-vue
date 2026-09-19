<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfvhcyw4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rfvhcyw4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:extension-eu" /></template>
