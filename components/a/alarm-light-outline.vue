<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mcxnry7tz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mcxnry7tz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:alarm-light-outline" /></template>
