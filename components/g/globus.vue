<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s1vhz79he.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s1vhz79he"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:globus" /></template>
