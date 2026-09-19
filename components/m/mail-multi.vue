<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7gw2sb4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i7gw2sb4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:mail-multi" /></template>
