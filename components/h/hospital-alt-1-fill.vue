<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swl0_-bvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="swl0_-bvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:hospital-alt-1-fill" /></template>
