<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/muqeto5-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="muqeto5-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:amaze" /></template>
