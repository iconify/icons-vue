<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wx72epa6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wx72epa6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:magentatv" /></template>
