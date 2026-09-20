<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhliwzgsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rhliwzgsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:flash-circle-fill" /></template>
