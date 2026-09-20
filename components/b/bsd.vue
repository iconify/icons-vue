<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i43fwks-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i43fwks-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:bsd" /></template>
