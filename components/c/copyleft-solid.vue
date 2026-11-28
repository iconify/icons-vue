<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xfhbzf_nd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xfhbzf_nd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:copyleft-solid" /></template>
