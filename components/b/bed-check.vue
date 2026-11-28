<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcw-0tbyh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vcw-0tbyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:bed-check" /></template>
