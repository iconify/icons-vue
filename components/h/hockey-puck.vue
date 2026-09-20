<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/warsr81xd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="warsr81xd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:hockey-puck" /></template>
