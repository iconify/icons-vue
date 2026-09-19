<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ti70t3bct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ti70t3bct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:dynalogic" /></template>
