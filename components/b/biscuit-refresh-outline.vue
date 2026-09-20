<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-2-_i5gv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m-2-_i5gv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:biscuit-refresh-outline" /></template>
