<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmj_96ose.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":24};
const content = `<path class="nmj_96ose"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:keyboard" /></template>
