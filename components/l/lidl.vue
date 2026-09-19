<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qg_w6jmdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qg_w6jmdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:lidl" /></template>
