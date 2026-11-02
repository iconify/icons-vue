<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/msmplhg-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="msmplhg-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:layout-line" /></template>
