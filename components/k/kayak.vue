<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pcyt9acpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pcyt9acpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:kayak" /></template>
