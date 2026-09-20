<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4z6z2bit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x4z6z2bit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:developer-board" /></template>
