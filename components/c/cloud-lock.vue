<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rch-wrbix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rch-wrbix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:cloud-lock" /></template>
