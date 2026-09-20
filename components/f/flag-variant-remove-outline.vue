<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xo4h86buk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xo4h86buk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:flag-variant-remove-outline" /></template>
