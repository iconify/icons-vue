<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wlw62wbed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wlw62wbed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:apple" /></template>
