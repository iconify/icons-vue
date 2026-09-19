<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhc-ifv-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jhc-ifv-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:data-transfer-down" /></template>
