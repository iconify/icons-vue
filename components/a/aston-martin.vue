<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xen0-cbeq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xen0-cbeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:aston-martin" /></template>
