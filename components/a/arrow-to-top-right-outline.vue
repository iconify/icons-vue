<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qetjnn09m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qetjnn09m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-to-top-right-outline" /></template>
