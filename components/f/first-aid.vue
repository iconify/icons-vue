<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xandkdpjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="xandkdpjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:first-aid" /></template>
