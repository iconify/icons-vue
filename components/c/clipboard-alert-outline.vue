<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-ksqghyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x-ksqghyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clipboard-alert-outline" /></template>
