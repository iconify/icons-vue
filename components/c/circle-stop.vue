<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nnf2dtqof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nnf2dtqof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-stop" /></template>
