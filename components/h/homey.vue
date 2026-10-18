<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sgswwlbxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sgswwlbxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:homey" /></template>
